<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4srbk-ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c4srbk-ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:bullhorn" {...props}></Icon>
