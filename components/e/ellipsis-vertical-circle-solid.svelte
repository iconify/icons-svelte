<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv7f0p25w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv7f0p25w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:ellipsis-vertical-circle-solid" {...props}></Icon>
