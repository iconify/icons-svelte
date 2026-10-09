<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij6cj4rwy.css';
import '../../css/u/ubti_-buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ij6cj4rwy"/><path class="ubti_-buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:baby-48-bold" {...props}></Icon>
