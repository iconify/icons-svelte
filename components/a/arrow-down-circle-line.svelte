<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi3chnf-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi3chnf-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-circle-line" {...props}></Icon>
