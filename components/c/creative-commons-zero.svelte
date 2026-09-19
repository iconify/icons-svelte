<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4b4ymh5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o4b4ymh5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:creative-commons-zero" {...props}></Icon>
