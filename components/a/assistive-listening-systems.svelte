<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km7n7_jaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="km7n7_jaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:assistive-listening-systems" {...props}></Icon>
