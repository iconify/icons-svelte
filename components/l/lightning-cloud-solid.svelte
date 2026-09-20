<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opoqdejcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="opoqdejcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:lightning-cloud-solid" {...props}></Icon>
