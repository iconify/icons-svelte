<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km03pubxo.css';
import '../../css/s/sodknibgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km03pubxo"/><path class="sodknibgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:product-subscriptions-outlined" {...props}></Icon>
