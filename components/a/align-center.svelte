<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4m27vkmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4m27vkmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-center" {...props}></Icon>
