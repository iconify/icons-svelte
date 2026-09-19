<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdk6xlj0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="qdk6xlj0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:circle-thin" {...props}></Icon>
