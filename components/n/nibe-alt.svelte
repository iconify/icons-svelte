<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vikohac2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vikohac2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nibe-alt" {...props}></Icon>
