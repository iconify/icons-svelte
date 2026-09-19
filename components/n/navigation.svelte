<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de78-xbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de78-xbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:navigation" {...props}></Icon>
