<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d78mwylyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d78mwylyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:filter-2" {...props}></Icon>
