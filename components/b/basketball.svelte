<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi-x-qcsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi-x-qcsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:basketball" {...props}></Icon>
