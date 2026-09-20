<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if30i5bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="if30i5bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:calendar-mark" {...props}></Icon>
