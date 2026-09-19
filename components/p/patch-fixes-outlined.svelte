<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km1ccqbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km1ccqbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:patch-fixes-outlined" {...props}></Icon>
