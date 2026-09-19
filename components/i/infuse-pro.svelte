<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugm998b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugm998b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:infuse-pro" {...props}></Icon>
