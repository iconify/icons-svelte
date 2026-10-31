<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex9s0kk5d.css';
import '../../css/a/a_7jv01nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ex9s0kk5d"/><path class="a_7jv01nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:albania" {...props}></Icon>
