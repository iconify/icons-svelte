<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikrpjh-ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikrpjh-ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hilton-hotels-resorts" {...props}></Icon>
