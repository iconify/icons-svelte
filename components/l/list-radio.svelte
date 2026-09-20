<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctl0kjb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctl0kjb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-radio" {...props}></Icon>
