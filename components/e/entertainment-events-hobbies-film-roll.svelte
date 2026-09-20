<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-th10mjr.css';
import '../../css/r/rndt691qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n-th10mjr"/><path class="rndt691qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-film-roll" {...props}></Icon>
