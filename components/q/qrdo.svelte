<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjmrwubzx.css';
import '../../css/r/roph-ga5n.css';
import '../../css/t/tu9oyqbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjmrwubzx"/><path class="roph-ga5n"/><path class="tu9oyqbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:qrdo" {...props}></Icon>
