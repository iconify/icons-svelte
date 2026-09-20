<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w308l4u6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w308l4u6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-right" {...props}></Icon>
