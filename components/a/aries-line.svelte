<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq9diw0mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq9diw0mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aries-line" {...props}></Icon>
