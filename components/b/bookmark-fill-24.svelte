<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj03jsb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj03jsb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-fill-24" {...props}></Icon>
