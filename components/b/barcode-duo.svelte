<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zldz03bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zldz03bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:barcode-duo" {...props}></Icon>
