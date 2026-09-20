<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bztwfrbon.css';
import '../../css/p/pb328ubdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bztwfrbon"/><path class="pb328ubdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:fire" {...props}></Icon>
