<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgb2-fblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgb2-fblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-5-fill" {...props}></Icon>
