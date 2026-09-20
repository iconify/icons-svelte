<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kisnkvbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kisnkvbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-app-line" {...props}></Icon>
