<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sws_sk_no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sws_sk_no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-tray-solid" {...props}></Icon>
