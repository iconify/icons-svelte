<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c61h6ccxp.css';
import '../../css/g/gulam1fal.css';
import '../../css/c/ccqy6rbku.css';
import '../../css/f/f86xz6sdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="c61h6ccxp"/><path class="gulam1fal"/><circle class="ccqy6rbku"/><path class="f86xz6sdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-satellite" {...props}></Icon>
