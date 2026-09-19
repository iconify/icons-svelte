<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id8txxh5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id8txxh5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lotus" {...props}></Icon>
