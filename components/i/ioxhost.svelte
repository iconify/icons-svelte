<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iruil4alm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iruil4alm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ioxhost" {...props}></Icon>
