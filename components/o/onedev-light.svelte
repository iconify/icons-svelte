<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvj0q6bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvj0q6bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onedev-light" {...props}></Icon>
