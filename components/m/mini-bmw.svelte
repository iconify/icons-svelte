<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8m1s5y6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8m1s5y6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mini-bmw" {...props}></Icon>
