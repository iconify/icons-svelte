<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2lq4ibgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2lq4ibgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decimal-decrease" {...props}></Icon>
