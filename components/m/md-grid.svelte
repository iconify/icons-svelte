<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el3ty7ptn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="el3ty7ptn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-grid" {...props}></Icon>
