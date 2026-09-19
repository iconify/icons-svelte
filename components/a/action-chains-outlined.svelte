<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0ozv0b7j.css';
import '../../css/o/o3tx_8bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0ozv0b7j"/><path class="o3tx_8bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:action-chains-outlined" {...props}></Icon>
