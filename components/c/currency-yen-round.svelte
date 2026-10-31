<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az39e9u_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az39e9u_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-yen-round" {...props}></Icon>
