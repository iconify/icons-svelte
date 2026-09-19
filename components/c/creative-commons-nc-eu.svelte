<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf51w1b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gf51w1b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:creative-commons-nc-eu" {...props}></Icon>
