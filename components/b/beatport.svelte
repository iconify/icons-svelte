<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwmq47vio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwmq47vio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:beatport" {...props}></Icon>
