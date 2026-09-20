<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2ik1qbwi.css';
import '../../css/d/ddoe6f8-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2ik1qbwi"/><path class="ddoe6f8-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:preview-fill" {...props}></Icon>
