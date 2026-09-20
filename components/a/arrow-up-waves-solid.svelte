<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoboap-yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoboap-yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-waves-solid" {...props}></Icon>
