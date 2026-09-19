<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7id3ni7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7id3ni7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-right-solid" {...props}></Icon>
