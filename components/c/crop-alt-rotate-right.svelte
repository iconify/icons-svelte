<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi24fmf5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi24fmf5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:crop-alt-rotate-right" {...props}></Icon>
