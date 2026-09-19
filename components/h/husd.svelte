<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thf47n7_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="thf47n7_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:husd" {...props}></Icon>
