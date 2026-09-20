<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oldk_zc-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oldk_zc-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bookmark-upload-fill" {...props}></Icon>
