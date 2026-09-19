<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9isj2bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9isj2bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-duplicate" {...props}></Icon>
