<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzd7b5q2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzd7b5q2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:quiz" {...props}></Icon>
