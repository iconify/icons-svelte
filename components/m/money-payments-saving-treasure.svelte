<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm40es_yd.css';
import '../../css/l/ljwietbxp.css';
import '../../css/e/ecbf7mdmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vm40es_yd"/><path class="ljwietbxp"/><path class="ecbf7mdmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-saving-treasure" {...props}></Icon>
