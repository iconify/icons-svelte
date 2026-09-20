<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6178bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hn6178bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bootstrap-5" {...props}></Icon>
