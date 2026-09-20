<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjb1utuhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjb1utuhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pisa-tower-fill" {...props}></Icon>
