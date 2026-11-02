<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv3n77kdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3n77kdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chopsticks-line" {...props}></Icon>
