<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfneb3qce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nfneb3qce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-down-right-16" {...props}></Icon>
