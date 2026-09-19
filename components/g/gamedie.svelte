<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0ojfxbrx.css';
import '../../css/a/akenjqb-m.css';
import '../../css/a/a7ah0vuxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0ojfxbrx"/><path class="akenjqb-m"/><path class="a7ah0vuxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:gamedie" {...props}></Icon>
