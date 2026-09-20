<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq38ekbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wq38ekbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-type-ticket" {...props}></Icon>
