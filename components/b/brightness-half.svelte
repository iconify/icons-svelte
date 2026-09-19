<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvt8a1byh.css';
import '../../css/q/qfpw5-bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvt8a1byh"/><path class="qfpw5-bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:brightness-half" {...props}></Icon>
