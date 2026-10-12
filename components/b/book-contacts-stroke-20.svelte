<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d43t32b4m.css';
import '../../css/y/y6ixysbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d43t32b4m"/><path class="y6ixysbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-contacts-stroke-20" {...props}></Icon>
