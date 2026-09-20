<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwwxpnvpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwwxpnvpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up3-filled" {...props}></Icon>
