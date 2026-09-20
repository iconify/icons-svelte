<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gllgdykju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gllgdykju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-none" {...props}></Icon>
