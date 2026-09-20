<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0en27b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e0en27b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:environment" {...props}></Icon>
