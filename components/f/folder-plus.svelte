<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvpn05bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvpn05bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-plus" {...props}></Icon>
