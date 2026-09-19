<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-bjnwbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-bjnwbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-branch" {...props}></Icon>
