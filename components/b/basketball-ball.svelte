<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wffk06bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="wffk06bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:basketball-ball" {...props}></Icon>
