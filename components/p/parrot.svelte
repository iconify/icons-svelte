<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1crgvb3e.css';
import '../../css/t/t694e9bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":375,"height":512};
const content = `<path class="s1crgvb3e"/><path class="t694e9bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:parrot" {...props}></Icon>
