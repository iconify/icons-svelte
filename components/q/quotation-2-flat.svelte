<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qazrfyd2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qazrfyd2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:quotation-2-flat" {...props}></Icon>
