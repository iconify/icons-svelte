<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leiavflem.css';
import '../../css/a/aumpujaom.css';
import '../../css/y/yv4_o-byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="leiavflem"/><path class="aumpujaom"/><path class="yv4_o-byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-minimalistic-bold-duotone" {...props}></Icon>
