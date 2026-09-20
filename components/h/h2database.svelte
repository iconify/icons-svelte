<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrs-59bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrs-59bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:h2database" {...props}></Icon>
