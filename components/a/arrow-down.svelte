<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prs33ibbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="prs33ibbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-down" {...props}></Icon>
