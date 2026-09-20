<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po_imbccw.css';
import '../../css/v/vla37tbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po_imbccw"/><path class="vla37tbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-circle-duotone" {...props}></Icon>
