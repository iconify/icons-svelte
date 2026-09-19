<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_eu50mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bv_eu50mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-fill-gear" {...props}></Icon>
