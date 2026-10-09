<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-1_twbuv.css';
import '../../css/u/un8javbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d-1_twbuv"/><path class="un8javbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-48-bold" {...props}></Icon>
