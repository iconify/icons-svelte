<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubfaqzbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubfaqzbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:center-fill-20" {...props}></Icon>
