<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4q0anbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4q0anbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:robot-fill" {...props}></Icon>
