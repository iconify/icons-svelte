<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6ccxni9z.css';
import '../../css/i/iz9zsdbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6ccxni9z"/><path class="iz9zsdbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:money-withdraw" {...props}></Icon>
