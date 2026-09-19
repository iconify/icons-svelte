<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiu5-accd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiu5-accd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:repeat" {...props}></Icon>
