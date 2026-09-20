<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsgd_fb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":684,"height":1568};
const content = `<path class="zsgd_fb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ralph-lauren-dark" {...props}></Icon>
