<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alrf-1b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="alrf-1b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bag-suitcase-2-remix" {...props}></Icon>
