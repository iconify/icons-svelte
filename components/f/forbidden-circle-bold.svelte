<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7_w9-itf.css';
import '../../css/z/zn77u3fhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7_w9-itf"/><path class="zn77u3fhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forbidden-circle-bold" {...props}></Icon>
