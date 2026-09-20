<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckktg4bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckktg4bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prepbytes" {...props}></Icon>
