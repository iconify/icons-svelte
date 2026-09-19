<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_uzs2cum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_uzs2cum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:4x4-cell" {...props}></Icon>
