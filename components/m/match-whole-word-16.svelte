<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsrxd0bsy.css';
import '../../css/d/d7pg5sbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fsrxd0bsy"/><path class="d7pg5sbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:match-whole-word-16" {...props}></Icon>
