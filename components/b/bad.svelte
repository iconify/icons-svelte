<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rztsgpblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":679};
const content = `<path class="rztsgpblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bad" {...props}></Icon>
