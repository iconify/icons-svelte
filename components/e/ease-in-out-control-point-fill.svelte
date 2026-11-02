<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m67v-61ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m67v-61ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-out-control-point-fill" {...props}></Icon>
