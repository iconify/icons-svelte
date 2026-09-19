<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mui3o5b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mui3o5b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:balloon" {...props}></Icon>
