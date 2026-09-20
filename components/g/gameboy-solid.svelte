<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv_3-tbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fv_3-tbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gameboy-solid" {...props}></Icon>
