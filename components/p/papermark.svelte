<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtf2h3l6b.css';
import '../../css/a/a61ltbq0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xtf2h3l6b"/><path class="a61ltbq0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermark" {...props}></Icon>
