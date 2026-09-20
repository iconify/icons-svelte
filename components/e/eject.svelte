<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8gc-8b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="a8gc-8b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:eject" {...props}></Icon>
