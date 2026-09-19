<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux8ahf0rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ux8ahf0rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ember" {...props}></Icon>
