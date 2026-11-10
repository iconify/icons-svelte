<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj95kiqzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bj95kiqzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bevel" {...props}></Icon>
