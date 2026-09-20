<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct11--kks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ct11--kks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-transfer-horizontal-square-solid" {...props}></Icon>
