<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkm10qtia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkm10qtia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-warning-fill" {...props}></Icon>
