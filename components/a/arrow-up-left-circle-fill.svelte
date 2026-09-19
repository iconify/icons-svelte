<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x04vd8uuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x04vd8uuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-left-circle-fill" {...props}></Icon>
