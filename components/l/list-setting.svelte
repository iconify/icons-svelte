<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yycurmbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yycurmbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-setting" {...props}></Icon>
