<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laizaxi8c.css';
import '../../css/n/n32urigtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laizaxi8c"/><path class="n32urigtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:left-indent" {...props}></Icon>
