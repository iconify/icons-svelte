<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1sqlybxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1sqlybxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chevron-up-right" {...props}></Icon>
