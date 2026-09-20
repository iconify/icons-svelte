<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytr_51bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="ytr_51bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-pull-request" {...props}></Icon>
