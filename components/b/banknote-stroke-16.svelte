<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw7r68gtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iw7r68gtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:banknote-stroke-16" {...props}></Icon>
