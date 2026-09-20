<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqy2fdc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqy2fdc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head" {...props}></Icon>
