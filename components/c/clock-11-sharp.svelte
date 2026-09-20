<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxpiuoc7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxpiuoc7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-11-sharp" {...props}></Icon>
