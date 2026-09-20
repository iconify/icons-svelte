<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3u869byd.css';
import '../../css/a/ad-jgcc6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j3u869byd"/><path class="ad-jgcc6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:godot" {...props}></Icon>
