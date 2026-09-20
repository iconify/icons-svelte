<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnnl-ebgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnnl-ebgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-square-horiz-fill" {...props}></Icon>
