<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jozwl4ami.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jozwl4ami"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kite" {...props}></Icon>
