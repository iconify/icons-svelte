<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta8ksbbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta8ksbbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-off" {...props}></Icon>
