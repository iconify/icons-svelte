<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvkz25b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path clip-rule="evenodd" class="nvkz25b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:calculator-alt" {...props}></Icon>
