<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn8hsfb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gn8hsfb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:amazon-pay" {...props}></Icon>
