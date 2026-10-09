<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmkt2cc1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cmkt2cc1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-down-20" {...props}></Icon>
