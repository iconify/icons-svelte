<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfejm6x_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfejm6x_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-narrow-wide-fill" {...props}></Icon>
