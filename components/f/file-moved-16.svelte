<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9h9hwd0t.css';
import '../../css/g/g1xl1cbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f9h9hwd0t"/><path class="g1xl1cbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-moved-16" {...props}></Icon>
