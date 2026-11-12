<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_u2cyq9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_u2cyq9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-check" {...props}></Icon>
