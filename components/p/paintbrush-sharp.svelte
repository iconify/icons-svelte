<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvv4397cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvv4397cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paintbrush-sharp" {...props}></Icon>
