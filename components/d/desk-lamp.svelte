<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_8-66btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_8-66btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:desk-lamp" {...props}></Icon>
