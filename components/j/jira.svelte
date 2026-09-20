<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlfhbsb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mlfhbsb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:jira" {...props}></Icon>
