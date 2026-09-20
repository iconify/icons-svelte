<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xerq-bbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xerq-bbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-3-line" {...props}></Icon>
