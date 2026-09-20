<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbe_snv5s.css';
import '../../css/h/hxb2u__jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qbe_snv5s"/><path class="hxb2u__jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chef-toque-hat-solid" {...props}></Icon>
