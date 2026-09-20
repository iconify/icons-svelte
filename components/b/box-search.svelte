<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5q_jiej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi5q_jiej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-search" {...props}></Icon>
