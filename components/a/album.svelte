<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y07wqubtc.css';
import '../../css/w/wckr9kb1z.css';
import '../../css/h/hd5qmml4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="y07wqubtc"/><path class="wckr9kb1z"/><path class="hd5qmml4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:album" {...props}></Icon>
