<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt5mcm8zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tt5mcm8zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bell-slash-16" {...props}></Icon>
