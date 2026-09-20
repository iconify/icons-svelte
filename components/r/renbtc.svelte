<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wetsv3agd.css';
import '../../css/q/quihcfbar.css';
import '../../css/k/k8agsabod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wetsv3agd"/><path clip-rule="evenodd" class="quihcfbar"/><path class="k8agsabod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:renbtc" {...props}></Icon>
