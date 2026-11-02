<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/remfnhs2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="remfnhs2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bell-minus-fill" {...props}></Icon>
