<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj9bwkiqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj9bwkiqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:flat" {...props}></Icon>
