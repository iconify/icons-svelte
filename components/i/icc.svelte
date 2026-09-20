<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqvkt6b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqvkt6b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:icc" {...props}></Icon>
