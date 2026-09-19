<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en6zipc7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="en6zipc7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:recurring-event" {...props}></Icon>
