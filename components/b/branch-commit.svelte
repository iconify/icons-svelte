<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkbn97b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kkbn97b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:branch-commit" {...props}></Icon>
