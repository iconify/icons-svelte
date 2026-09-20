<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dktnxccgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dktnxccgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:equaliser" {...props}></Icon>
