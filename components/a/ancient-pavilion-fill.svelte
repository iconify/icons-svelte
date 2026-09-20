<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwpg2abjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwpg2abjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ancient-pavilion-fill" {...props}></Icon>
