<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efbm7bbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="efbm7bbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-added-16" {...props}></Icon>
