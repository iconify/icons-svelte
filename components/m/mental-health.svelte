<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdu0vibli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pdu0vibli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mental-health" {...props}></Icon>
