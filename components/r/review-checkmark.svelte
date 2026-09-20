<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-any57sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p-any57sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:review-checkmark" {...props}></Icon>
