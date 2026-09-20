<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys2c0-bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ys2c0-bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:medal" {...props}></Icon>
