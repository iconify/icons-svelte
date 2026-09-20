<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2px-ta7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c2px-ta7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:paper-airplane" {...props}></Icon>
