<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk7w1m6ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7w1m6ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drinks-2-fill" {...props}></Icon>
