<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/betyx0-oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="betyx0-oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:douban-read" {...props}></Icon>
