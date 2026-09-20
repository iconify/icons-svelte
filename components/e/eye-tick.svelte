<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn7l3uo8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn7l3uo8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-tick" {...props}></Icon>
