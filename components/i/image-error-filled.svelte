<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x78rb0q8y.css';
import '../../css/n/n8fw_acsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x78rb0q8y"/><path class="n8fw_acsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-error-filled" {...props}></Icon>
