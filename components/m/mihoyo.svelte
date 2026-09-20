<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5v31ibvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5v31ibvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mihoyo" {...props}></Icon>
