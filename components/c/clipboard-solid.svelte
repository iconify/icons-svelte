<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoe62lluo.css';
import '../../css/u/uy_7ftb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoe62lluo"/><path class="uy_7ftb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:clipboard-solid" {...props}></Icon>
