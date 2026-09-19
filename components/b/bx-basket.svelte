<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ift012_ct.css';
import '../../css/o/ockmixada.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ift012_ct"/><path class="ockmixada"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-basket" {...props}></Icon>
