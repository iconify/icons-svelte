<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwr0h7biq.css';
import '../../css/x/xcnr5ab-g.css';
import '../../css/t/t2w8mls_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jwr0h7biq"/><path class="xcnr5ab-g"/><path class="t2w8mls_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:mali" {...props}></Icon>
