<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7un7q-3o.css';
import '../../css/p/p8sne4bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7un7q-3o"/><path clip-rule="evenodd" class="p8sne4bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ncr" {...props}></Icon>
