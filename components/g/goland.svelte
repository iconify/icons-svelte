<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unzp673gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unzp673gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:goland" {...props}></Icon>
