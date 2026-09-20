<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvmhkibsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="xvmhkibsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:calendar" {...props}></Icon>
