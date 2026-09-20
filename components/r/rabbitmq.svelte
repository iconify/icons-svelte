<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgm3tebms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgm3tebms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rabbitmq" {...props}></Icon>
