<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id9bk0b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="id9bk0b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-stroke-12" {...props}></Icon>
