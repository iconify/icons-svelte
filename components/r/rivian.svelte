<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fccn48b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":202.395,"height":42.309,"left":-1.197,"top":-1.197};
const content = `<path class="fccn48b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rivian" {...props}></Icon>
