<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zon5_mjhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zon5_mjhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-expressionless-fill" {...props}></Icon>
