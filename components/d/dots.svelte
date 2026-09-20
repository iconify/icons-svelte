<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc-31ibxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc-31ibxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dots" {...props}></Icon>
