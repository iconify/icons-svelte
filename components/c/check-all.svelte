<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw1l_zb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jw1l_zb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:check-all" {...props}></Icon>
