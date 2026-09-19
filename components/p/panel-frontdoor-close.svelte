<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo2b0jzxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo2b0jzxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-frontdoor-close" {...props}></Icon>
