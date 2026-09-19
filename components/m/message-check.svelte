<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm4zdvz_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm4zdvz_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:message-check" {...props}></Icon>
