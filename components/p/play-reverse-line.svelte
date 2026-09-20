<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj9kt2-kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj9kt2-kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-reverse-line" {...props}></Icon>
