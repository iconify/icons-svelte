<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1is4rb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1is4rb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:distribute-horizontally" {...props}></Icon>
