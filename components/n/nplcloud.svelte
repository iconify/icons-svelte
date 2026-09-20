<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dulgvk_ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dulgvk_ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nplcloud" {...props}></Icon>
