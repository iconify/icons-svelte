<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlthwk80x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlthwk80x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:play-circle-fill" {...props}></Icon>
