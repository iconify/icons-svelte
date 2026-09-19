<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a06oteb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a06oteb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-crown" {...props}></Icon>
