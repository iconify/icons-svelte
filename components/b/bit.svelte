<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq5h7gcxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tq5h7gcxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bit" {...props}></Icon>
