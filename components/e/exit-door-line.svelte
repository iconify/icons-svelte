<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ci7lqxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ci7lqxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exit-door-line" {...props}></Icon>
