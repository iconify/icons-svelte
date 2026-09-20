<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk4ybvuoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk4ybvuoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:refresh-cw-sharp-fill" {...props}></Icon>
