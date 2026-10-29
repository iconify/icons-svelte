<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2pm3-mel.css';
import '../../css/i/id9ydeb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2pm3-mel"/><path class="id9ydeb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:quote" {...props}></Icon>
