<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boah2vobs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boah2vobs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-buckram-three" {...props}></Icon>
