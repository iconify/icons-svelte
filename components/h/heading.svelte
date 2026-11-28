<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbs0qqb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbs0qqb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heading" {...props}></Icon>
