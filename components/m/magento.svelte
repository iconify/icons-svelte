<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0-ckijfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-ckijfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:magento" {...props}></Icon>
