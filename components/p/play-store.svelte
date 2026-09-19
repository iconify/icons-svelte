<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am38jwbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am38jwbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:play-store" {...props}></Icon>
