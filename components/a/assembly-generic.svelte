<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3k5h1buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3k5h1buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-generic" {...props}></Icon>
