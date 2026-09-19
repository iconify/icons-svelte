<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps7v1ibub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ps7v1ibub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flask-fill" {...props}></Icon>
