<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa96ic2en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa96ic2en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:direction" {...props}></Icon>
