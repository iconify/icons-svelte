<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfgz-i8ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cfgz-i8ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:payment-recieve-7-remix" {...props}></Icon>
