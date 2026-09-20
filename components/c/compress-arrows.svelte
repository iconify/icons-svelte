<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiwv975yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwv975yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:compress-arrows" {...props}></Icon>
