<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0n90cc4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0n90cc4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bug-play" {...props}></Icon>
