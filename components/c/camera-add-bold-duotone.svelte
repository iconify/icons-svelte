<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxxr0xdbr.css';
import '../../css/g/ghd9kjblg.css';
import '../../css/z/z9kgvgb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxxr0xdbr"/><path clip-rule="evenodd" class="ghd9kjblg"/><path class="z9kgvgb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-add-bold-duotone" {...props}></Icon>
