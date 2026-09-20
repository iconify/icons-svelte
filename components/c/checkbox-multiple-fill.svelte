<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu_1temnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu_1temnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-multiple-fill" {...props}></Icon>
