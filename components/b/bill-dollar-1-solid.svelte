<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_cmk7-2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_cmk7-2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bill-dollar-1-solid" {...props}></Icon>
