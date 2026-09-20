<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m998mkbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m998mkbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gas-station-fuel-petroleum-solid" {...props}></Icon>
