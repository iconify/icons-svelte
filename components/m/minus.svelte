<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn8u5lb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn8u5lb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:minus" {...props}></Icon>
