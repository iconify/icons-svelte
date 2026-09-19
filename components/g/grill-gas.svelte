<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj10aeb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj10aeb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:grill-gas" {...props}></Icon>
