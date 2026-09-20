<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go8ehsr3x.css';
import '../../css/z/zut4dr69s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="go8ehsr3x"/><path class="zut4dr69s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:copyright" {...props}></Icon>
