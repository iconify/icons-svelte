<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od_856e-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od_856e-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-drop-down" {...props}></Icon>
