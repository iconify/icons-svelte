<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvsiy_b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvsiy_b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:protodotio" {...props}></Icon>
