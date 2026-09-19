<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzn7rdbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":448};
const content = `<path class="tzn7rdbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:checked" {...props}></Icon>
