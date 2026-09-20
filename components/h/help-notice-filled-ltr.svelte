<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2b68bbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j2b68bbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:help-notice-filled-ltr" {...props}></Icon>
