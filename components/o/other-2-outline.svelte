<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm4bagw4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4bagw4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:other-2-outline" {...props}></Icon>
