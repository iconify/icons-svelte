<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxq523bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxq523bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-right-square-fill" {...props}></Icon>
