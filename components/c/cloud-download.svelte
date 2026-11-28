<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bng7-4bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bng7-4bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-download" {...props}></Icon>
