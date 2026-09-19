<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z38kx1b1d.css';
import '../../css/e/ew4cdbbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z38kx1b1d"/><path clip-rule="evenodd" class="ew4cdbbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:arrow-left-outline" {...props}></Icon>
