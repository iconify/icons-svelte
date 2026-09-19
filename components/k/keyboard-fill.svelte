<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpvz-r1bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cpvz-r1bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:keyboard-fill" {...props}></Icon>
