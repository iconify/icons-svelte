<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwb8jyb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pwb8jyb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:delicious" {...props}></Icon>
