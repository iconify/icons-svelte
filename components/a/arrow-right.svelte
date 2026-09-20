<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1e1eib7x.css';
import '../../css/f/f1pn7ybqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="o1e1eib7x"/><path class="f1pn7ybqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:arrow-right" {...props}></Icon>
