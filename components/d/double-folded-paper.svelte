<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abs78vbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="abs78vbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:double-folded-paper" {...props}></Icon>
