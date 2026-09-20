<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0oc23b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0oc23b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mic-off-fill" {...props}></Icon>
