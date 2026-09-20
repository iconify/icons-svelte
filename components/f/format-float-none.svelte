<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svdu2hbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svdu2hbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-float-none" {...props}></Icon>
