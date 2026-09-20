<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb0ez_bdu.css';
import '../../css/j/j4olmxbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb0ez_bdu"/><path class="j4olmxbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:book-open-duotone" {...props}></Icon>
