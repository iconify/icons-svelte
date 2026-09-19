<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s36yk8bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s36yk8bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-align-middle" {...props}></Icon>
