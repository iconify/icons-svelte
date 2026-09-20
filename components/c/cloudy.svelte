<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu9am2bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu9am2bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloudy" {...props}></Icon>
