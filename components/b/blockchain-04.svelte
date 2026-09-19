<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve37pubxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve37pubxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:blockchain-04" {...props}></Icon>
