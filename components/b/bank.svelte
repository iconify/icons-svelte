<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc4m7k-7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc4m7k-7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:bank" {...props}></Icon>
