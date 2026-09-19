<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byxt0tfsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="byxt0tfsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:rebel" {...props}></Icon>
