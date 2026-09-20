<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toc7-6bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toc7-6bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-baht-fill" {...props}></Icon>
