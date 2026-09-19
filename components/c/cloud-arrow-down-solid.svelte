<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj-j1uuvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj-j1uuvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-down-solid" {...props}></Icon>
