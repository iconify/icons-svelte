<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcd7ccb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcd7ccb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-left-circle-line" {...props}></Icon>
