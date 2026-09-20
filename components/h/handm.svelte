<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1x2mgbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1x2mgbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:handm" {...props}></Icon>
