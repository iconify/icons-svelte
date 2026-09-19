<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na7l5acoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na7l5acoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reflect-horizontal-alt" {...props}></Icon>
