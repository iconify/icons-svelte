<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxx6fwb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxx6fwb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-left-circle-fill" {...props}></Icon>
