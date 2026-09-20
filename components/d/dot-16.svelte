<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfslq-b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cfslq-b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dot-16" {...props}></Icon>
