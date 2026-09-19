<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyrkxgbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyrkxgbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lift-in-window-open-alt-2" {...props}></Icon>
