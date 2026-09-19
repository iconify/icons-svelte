<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2om1gb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n2om1gb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:puzzle" {...props}></Icon>
