<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1k-614nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i1k-614nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-commit-outline" {...props}></Icon>
