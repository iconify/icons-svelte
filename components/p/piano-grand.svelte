<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjn5kuzfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjn5kuzfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:piano-grand" {...props}></Icon>
