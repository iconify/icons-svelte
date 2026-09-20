<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnv1z5w0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnv1z5w0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heater" {...props}></Icon>
