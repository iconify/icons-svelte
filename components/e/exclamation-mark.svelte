<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnfa8zd7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bnfa8zd7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:exclamation-mark" {...props}></Icon>
