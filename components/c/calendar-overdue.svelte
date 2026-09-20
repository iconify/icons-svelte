<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1623dbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j1623dbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:calendar-overdue" {...props}></Icon>
