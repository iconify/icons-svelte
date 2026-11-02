<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahyghgztp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahyghgztp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-2-fill" {...props}></Icon>
