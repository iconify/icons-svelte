<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqyoi2ukf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqyoi2ukf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-wall-nyro-flood" {...props}></Icon>
