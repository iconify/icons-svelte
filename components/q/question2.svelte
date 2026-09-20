<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2qtsccxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p2qtsccxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:question2" {...props}></Icon>
