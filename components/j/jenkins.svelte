<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9vwxwshl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vwxwshl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jenkins" {...props}></Icon>
