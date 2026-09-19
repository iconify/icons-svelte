<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6s60-s9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":622};
const content = `<path class="w6s60-s9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:friend" {...props}></Icon>
