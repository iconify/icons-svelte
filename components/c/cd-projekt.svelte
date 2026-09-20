<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwdb95dxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwdb95dxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cd-projekt" {...props}></Icon>
