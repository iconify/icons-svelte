<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7tz73t3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e7tz73t3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:label-small-filled" {...props}></Icon>
