<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvypdlbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvypdlbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:fire-fill" {...props}></Icon>
