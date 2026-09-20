<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka5_0n05d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka5_0n05d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-exclamation" {...props}></Icon>
