<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_8z_56lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i_8z_56lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bookmark-16" {...props}></Icon>
