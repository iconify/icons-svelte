<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvvdxrb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvvdxrb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:7zip" {...props}></Icon>
