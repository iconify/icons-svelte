<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aazs-57qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800};
const content = `<path class="aazs-57qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alteryx" {...props}></Icon>
