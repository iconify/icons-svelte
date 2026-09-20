<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpqas1ggj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpqas1ggj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deviant-art-logo-2-block" {...props}></Icon>
