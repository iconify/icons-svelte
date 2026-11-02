<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjhzmob8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjhzmob8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-check-line" {...props}></Icon>
