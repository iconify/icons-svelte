<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9g4ovbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="y9g4ovbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:forward-circle-f" {...props}></Icon>
