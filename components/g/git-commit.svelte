<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqraibc5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="tqraibc5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-commit" {...props}></Icon>
