<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewnchtbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewnchtbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egyptian-pyramids-fill" {...props}></Icon>
