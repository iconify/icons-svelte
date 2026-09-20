<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_w-ihbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_w-ihbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:globe" {...props}></Icon>
