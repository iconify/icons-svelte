<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmq5sba2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hmq5sba2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:dribbble-square" {...props}></Icon>
