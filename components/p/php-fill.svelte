<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_w8biqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_w8biqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:php-fill" {...props}></Icon>
