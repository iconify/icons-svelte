<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4bs_w5rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l4bs_w5rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:file-check-alternate-solid" {...props}></Icon>
