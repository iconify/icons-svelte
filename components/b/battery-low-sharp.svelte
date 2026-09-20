<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9d_yabpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9d_yabpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery-low-sharp" {...props}></Icon>
