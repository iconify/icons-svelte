<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4yui_ytw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4yui_ytw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-love-line" {...props}></Icon>
