<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4i8rebks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4i8rebks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:braces" {...props}></Icon>
