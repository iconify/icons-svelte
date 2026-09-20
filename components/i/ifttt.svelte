<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq3x7s-mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq3x7s-mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ifttt" {...props}></Icon>
