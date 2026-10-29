<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv18b4bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv18b4bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-compare-solid" {...props}></Icon>
