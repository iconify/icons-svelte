<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwg9x0t8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwg9x0t8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hierarchy-square2-filled" {...props}></Icon>
