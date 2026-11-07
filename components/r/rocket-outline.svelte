<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c773tpndo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c773tpndo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-outline" {...props}></Icon>
