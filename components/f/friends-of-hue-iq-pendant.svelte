<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6g0efk1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6g0efk1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-iq-pendant" {...props}></Icon>
