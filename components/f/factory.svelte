<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zynt9nlma.css';
import '../../css/m/mp8j32oal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zynt9nlma"/><path class="mp8j32oal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:factory" {...props}></Icon>
