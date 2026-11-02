<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng0z8-bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng0z8-bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disabled-fill" {...props}></Icon>
