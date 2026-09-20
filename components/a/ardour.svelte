<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wty7bjlol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wty7bjlol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ardour" {...props}></Icon>
