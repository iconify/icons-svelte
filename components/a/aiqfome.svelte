<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kosp5ac3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kosp5ac3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aiqfome" {...props}></Icon>
