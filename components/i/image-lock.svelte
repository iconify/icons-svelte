<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djqr_wbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djqr_wbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-lock" {...props}></Icon>
