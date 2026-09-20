<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssv2r9bnu.css';
import '../../css/o/o2pei4b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssv2r9bnu"/><path class="o2pei4b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:garbage-bin-bold" {...props}></Icon>
