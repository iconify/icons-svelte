<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivy_7zb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ivy_7zb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:refresh-doing-outline" {...props}></Icon>
