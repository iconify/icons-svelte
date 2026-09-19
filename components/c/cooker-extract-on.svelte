<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5tfsv9lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5tfsv9lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cooker-extract-on" {...props}></Icon>
