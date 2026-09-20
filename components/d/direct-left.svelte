<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnhzx54km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnhzx54km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:direct-left" {...props}></Icon>
