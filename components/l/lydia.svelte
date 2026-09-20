<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ch7sbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ch7sbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lydia" {...props}></Icon>
