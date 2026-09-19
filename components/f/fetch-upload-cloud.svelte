<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6z_u39ix.css';
import '../../css/k/kfaykc6be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m6z_u39ix"/><path class="kfaykc6be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fetch-upload-cloud" {...props}></Icon>
