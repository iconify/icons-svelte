<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poyy-gyea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poyy-gyea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-alert" {...props}></Icon>
