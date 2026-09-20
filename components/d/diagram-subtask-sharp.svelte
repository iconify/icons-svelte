<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2itfyboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2itfyboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-subtask-sharp" {...props}></Icon>
