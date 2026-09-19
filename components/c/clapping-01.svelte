<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm3dx-j5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm3dx-j5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:clapping-01" {...props}></Icon>
