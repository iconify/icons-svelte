<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6tgntbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6tgntbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-buffer-solid" {...props}></Icon>
