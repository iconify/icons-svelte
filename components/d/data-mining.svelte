<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_gr6ubgr.css';
import '../../css/g/g77xgdc7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_gr6ubgr"/><path class="g77xgdc7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:data-mining" {...props}></Icon>
