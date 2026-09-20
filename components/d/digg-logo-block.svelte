<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5nb-51af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5nb-51af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:digg-logo-block" {...props}></Icon>
