<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0d7-ntjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":366.08,"height":298.83,"left":-3.29,"top":29.96};
const content = `<path class="z0d7-ntjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:in-toto-dark" {...props}></Icon>
