<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dowbeobsa.css';
import '../../css/z/ziuz1w_mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dowbeobsa"/><path class="ziuz1w_mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:banknotepound" {...props}></Icon>
