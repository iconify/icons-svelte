<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvstsdrro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvstsdrro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-rabbit-hat" {...props}></Icon>
