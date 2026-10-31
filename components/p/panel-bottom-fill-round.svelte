<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhwqw6bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhwqw6bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-bottom-fill-round" {...props}></Icon>
