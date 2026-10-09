<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjt2vnb6p.css';
import '../../css/a/axzye1lxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pjt2vnb6p"/><path class="axzye1lxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:copy-20" {...props}></Icon>
