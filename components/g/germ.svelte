<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_t_n4bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_t_n4bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:germ" {...props}></Icon>
