<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7hh0ng0w.css';
import '../../css/c/cdujlmbca.css';
import '../../css/t/tpz02j0hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7hh0ng0w"/><path class="cdujlmbca"/><path class="tpz02j0hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cam-20-bold" {...props}></Icon>
