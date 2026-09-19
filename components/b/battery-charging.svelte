<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxaj23pjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxaj23pjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:battery-charging" {...props}></Icon>
