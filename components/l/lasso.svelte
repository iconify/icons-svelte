<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1v0u_7-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s1v0u_7-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:lasso" {...props}></Icon>
