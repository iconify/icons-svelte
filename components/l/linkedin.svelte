<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrdg1_n9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrdg1_n9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:linkedin" {...props}></Icon>
