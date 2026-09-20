<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-e5j90ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-e5j90ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plug-socket-switzerland" {...props}></Icon>
