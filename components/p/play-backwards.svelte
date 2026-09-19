<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdt6ofbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdt6ofbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-backwards" {...props}></Icon>
