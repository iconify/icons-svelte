<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1ra9z4op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1ra9z4op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:desk-lamp" {...props}></Icon>
