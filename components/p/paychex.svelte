<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl7u15blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl7u15blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paychex" {...props}></Icon>
