<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx77gjbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx77gjbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dharmachakra" {...props}></Icon>
