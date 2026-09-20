<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqdrd48yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdrd48yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bt" {...props}></Icon>
