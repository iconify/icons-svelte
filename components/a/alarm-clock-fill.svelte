<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr_xah05r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_xah05r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:alarm-clock-fill" {...props}></Icon>
