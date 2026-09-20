<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwa1tob8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gwa1tob8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-in-stroller" {...props}></Icon>
