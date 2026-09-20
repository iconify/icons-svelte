<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9sinp6my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sinp6my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lock-unlock-line" {...props}></Icon>
