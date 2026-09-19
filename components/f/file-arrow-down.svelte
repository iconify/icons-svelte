<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t88t3ip3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t88t3ip3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-arrow-down" {...props}></Icon>
