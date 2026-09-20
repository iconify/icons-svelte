<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyr3f_b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyr3f_b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googledomains" {...props}></Icon>
