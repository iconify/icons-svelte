<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1j8od6ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b1j8od6ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:magnifying-glass" {...props}></Icon>
