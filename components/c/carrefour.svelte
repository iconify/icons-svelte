<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapbn_but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qapbn_but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:carrefour" {...props}></Icon>
