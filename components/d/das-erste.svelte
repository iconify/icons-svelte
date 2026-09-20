<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esy24bk8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esy24bk8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:das-erste" {...props}></Icon>
