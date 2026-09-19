<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj0xx1u2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sj0xx1u2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:creative-commons-share" {...props}></Icon>
