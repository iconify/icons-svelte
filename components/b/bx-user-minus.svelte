<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2ep2ccux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2ep2ccux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-user-minus" {...props}></Icon>
