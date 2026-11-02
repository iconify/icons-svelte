<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ef0i5xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ef0i5xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-small-fill" {...props}></Icon>
