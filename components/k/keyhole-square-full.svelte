<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp78fnb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp78fnb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:keyhole-square-full" {...props}></Icon>
