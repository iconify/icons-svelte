<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r84hslb4j.css';
import '../../css/w/wjj22sddn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r84hslb4j"/><path class="wjj22sddn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:reset" {...props}></Icon>
