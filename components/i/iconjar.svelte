<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od6qm09ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od6qm09ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:iconjar" {...props}></Icon>
