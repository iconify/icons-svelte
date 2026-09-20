<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk0a1hbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk0a1hbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:repeat-one-fill" {...props}></Icon>
