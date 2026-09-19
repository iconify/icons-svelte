<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbrqyjb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="mbrqyjb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:adobe" {...props}></Icon>
