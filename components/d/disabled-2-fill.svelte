<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_zw-6bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_zw-6bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disabled-2-fill" {...props}></Icon>
