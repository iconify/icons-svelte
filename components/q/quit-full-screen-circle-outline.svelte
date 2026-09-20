<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5y2qnprl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5y2qnprl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-full-screen-circle-outline" {...props}></Icon>
