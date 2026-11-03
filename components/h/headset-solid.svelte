<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_hrzfb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_hrzfb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headset-solid" {...props}></Icon>
