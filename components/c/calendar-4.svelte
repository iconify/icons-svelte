<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaijz-d4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yaijz-d4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:calendar-4" {...props}></Icon>
