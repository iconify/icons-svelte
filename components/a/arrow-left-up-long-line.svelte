<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyflgxb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyflgxb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-up-long-line" {...props}></Icon>
