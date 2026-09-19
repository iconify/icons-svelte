<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjj48ibfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjj48ibfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:plug-filled" {...props}></Icon>
