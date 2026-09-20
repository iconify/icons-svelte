<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evn9cubmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evn9cubmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-diamond-fill" {...props}></Icon>
