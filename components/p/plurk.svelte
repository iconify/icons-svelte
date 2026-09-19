<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd_9zebhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pd_9zebhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:plurk" {...props}></Icon>
