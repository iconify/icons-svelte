<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxy6xi-um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jxy6xi-um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:microphone-off" {...props}></Icon>
