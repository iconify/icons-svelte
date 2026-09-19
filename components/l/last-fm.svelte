<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fht-7-b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fht-7-b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:last-fm" {...props}></Icon>
