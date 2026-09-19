<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9dow-b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f9dow-b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:picture" {...props}></Icon>
