<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc9ndrb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc9ndrb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:pentagon" {...props}></Icon>
