<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m32t7pb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m32t7pb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:charging-pile-line" {...props}></Icon>
