<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7-mqmb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7-mqmb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-project" {...props}></Icon>
