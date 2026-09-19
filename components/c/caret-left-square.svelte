<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwcanry2a.css';
import '../../css/c/c98at3bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcanry2a"/><path class="c98at3bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:caret-left-square" {...props}></Icon>
