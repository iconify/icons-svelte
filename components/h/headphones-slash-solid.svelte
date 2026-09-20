<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcc0w7qat.css';
import '../../css/a/aqwncob1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcc0w7qat"/><path class="aqwncob1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-slash-solid" {...props}></Icon>
