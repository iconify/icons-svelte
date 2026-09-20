<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k17ewccpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k17ewccpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:news-2-fill" {...props}></Icon>
