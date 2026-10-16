<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb3dnqqxo.css';
import '../../css/c/cds46xnib.css';
import '../../css/n/nvw6mps9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xb3dnqqxo"/><path class="cds46xnib"/><path class="nvw6mps9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-plus-20" {...props}></Icon>
