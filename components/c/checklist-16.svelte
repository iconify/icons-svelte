<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v__un6b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v__un6b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:checklist-16" {...props}></Icon>
