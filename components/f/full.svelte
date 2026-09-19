<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgbwi1bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="sgbwi1bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:full" {...props}></Icon>
