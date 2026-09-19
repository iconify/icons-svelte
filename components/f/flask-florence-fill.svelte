<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waq_d7rbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="waq_d7rbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flask-florence-fill" {...props}></Icon>
