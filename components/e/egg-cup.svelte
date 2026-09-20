<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipimt7btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipimt7btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:egg-cup" {...props}></Icon>
