<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gua1uqcfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gua1uqcfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-arrow-right-outline" {...props}></Icon>
