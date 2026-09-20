<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5f070bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="j5f070bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:circumflex" {...props}></Icon>
