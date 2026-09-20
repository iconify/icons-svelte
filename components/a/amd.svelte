<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j39z0vbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j39z0vbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amd" {...props}></Icon>
