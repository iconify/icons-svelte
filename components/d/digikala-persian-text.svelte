<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-5x6nayi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":153,"height":42};
const content = `<path clip-rule="evenodd" class="r-5x6nayi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:digikala-persian-text" {...props}></Icon>
