<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymw3uvdzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymw3uvdzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bilibili-fill" {...props}></Icon>
