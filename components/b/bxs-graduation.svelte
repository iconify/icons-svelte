<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtvcw1bvs.css';
import '../../css/w/w8cjmh64r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvcw1bvs"/><path class="w8cjmh64r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-graduation" {...props}></Icon>
