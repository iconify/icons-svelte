<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc07x3xxz.css';
import '../../css/v/vif4xej-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hc07x3xxz"/><path class="vif4xej-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-top-open-filled" {...props}></Icon>
