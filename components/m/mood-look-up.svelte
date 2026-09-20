<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egx-80bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egx-80bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-look-up" {...props}></Icon>
