<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug_839j4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ug_839j4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linear" {...props}></Icon>
