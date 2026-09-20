<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6-6p29ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6-6p29ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-remove" {...props}></Icon>
