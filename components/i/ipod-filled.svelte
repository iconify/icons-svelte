<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rus7agb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rus7agb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ipod-filled" {...props}></Icon>
