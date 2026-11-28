<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpod5-wad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zpod5-wad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-compare-duotone" {...props}></Icon>
