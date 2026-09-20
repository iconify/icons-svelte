<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hotaktb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hotaktb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mqtt" {...props}></Icon>
