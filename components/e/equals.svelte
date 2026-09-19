<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6h_28ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="th6h_28ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:equals" {...props}></Icon>
