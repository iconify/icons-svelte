<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs6lblcao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs6lblcao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apple-podcasts" {...props}></Icon>
