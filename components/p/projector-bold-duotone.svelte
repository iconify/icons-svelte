<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3hjlsbmw.css';
import '../../css/w/wt1vqqboi.css';
import '../../css/l/l0umolbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3hjlsbmw"/><path class="wt1vqqboi"/><path class="l0umolbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:projector-bold-duotone" {...props}></Icon>
