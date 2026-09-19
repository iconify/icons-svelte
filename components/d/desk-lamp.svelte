<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez4hw9bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ez4hw9bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:desk-lamp" {...props}></Icon>
