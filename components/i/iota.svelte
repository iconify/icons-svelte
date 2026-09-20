<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upop3rb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upop3rb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:iota" {...props}></Icon>
