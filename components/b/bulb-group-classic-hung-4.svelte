<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvsxk8p_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvsxk8p_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-classic-hung-4" {...props}></Icon>
