<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcumv1bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zcumv1bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:menu2-outline" {...props}></Icon>
