<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rowqs7baj.css';
import '../../css/p/p_tfwbcxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rowqs7baj"/><path class="p_tfwbcxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-notification-fill" {...props}></Icon>
