<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olirf2bph.css';
import '../../css/q/qz4yqq5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olirf2bph"/><path class="qz4yqq5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:coinex-smart-chain" {...props}></Icon>
