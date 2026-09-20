<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pch8ymubu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pch8ymubu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:first" {...props}></Icon>
