<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp6t2j1op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pp6t2j1op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:eye-16" {...props}></Icon>
