<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nap9lkbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nap9lkbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:houzz" {...props}></Icon>
