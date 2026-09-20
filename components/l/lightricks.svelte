<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjo5abva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrjo5abva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lightricks" {...props}></Icon>
