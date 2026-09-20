<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chy9vjf-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chy9vjf-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emphasis-cn" {...props}></Icon>
