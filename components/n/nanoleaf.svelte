<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcl7_1caz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcl7_1caz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf" {...props}></Icon>
