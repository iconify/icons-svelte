<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1na5ebkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1na5ebkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-seat-cooler" {...props}></Icon>
