<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ievdxcc9u.css';
import '../../css/x/xcuj9xz1r.css';
import '../../css/c/cfvelzb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ievdxcc9u"/><path class="xcuj9xz1r"/><path class="cfvelzb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:layers" {...props}></Icon>
