<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7k76abce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7k76abce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:loop-1" {...props}></Icon>
