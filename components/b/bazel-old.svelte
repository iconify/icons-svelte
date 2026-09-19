<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz1vtzbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":355,"height":512};
const content = `<path class="cz1vtzbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bazel-old" {...props}></Icon>
