<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7b6xyuqs.css';
import '../../css/e/ez6lwcbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7b6xyuqs"/><path class="ez6lwcbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-school" {...props}></Icon>
