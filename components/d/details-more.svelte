<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u828rdhnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u828rdhnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:details-more" {...props}></Icon>
