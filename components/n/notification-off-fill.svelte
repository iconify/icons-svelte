<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5pgg5kgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5pgg5kgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-off-fill" {...props}></Icon>
