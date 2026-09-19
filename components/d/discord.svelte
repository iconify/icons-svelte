<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5xp_8gtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="o5xp_8gtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:discord" {...props}></Icon>
