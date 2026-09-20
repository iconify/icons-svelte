<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm41kn5-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm41kn5-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:monkey-tie" {...props}></Icon>
