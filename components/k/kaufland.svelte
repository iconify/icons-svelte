<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztgohcc8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztgohcc8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kaufland" {...props}></Icon>
