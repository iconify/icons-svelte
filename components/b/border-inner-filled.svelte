<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxo__5f1j.css';
import '../../css/u/uq4zqzbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxo__5f1j"/><path class="uq4zqzbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-inner-filled" {...props}></Icon>
