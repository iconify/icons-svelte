<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl8frbc0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8frbc0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:broccoli-filled" {...props}></Icon>
