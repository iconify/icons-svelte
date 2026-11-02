<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex35hwhyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex35hwhyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-user-fill" {...props}></Icon>
