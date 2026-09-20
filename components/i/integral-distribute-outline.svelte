<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-21--bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f-21--bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:integral-distribute-outline" {...props}></Icon>
