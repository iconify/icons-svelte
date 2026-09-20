<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n08u8g0bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n08u8g0bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grapheneos" {...props}></Icon>
