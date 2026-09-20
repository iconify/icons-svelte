<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnopl_b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xnopl_b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-commit-solid" {...props}></Icon>
