<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivs45cbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivs45cbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-1" {...props}></Icon>
