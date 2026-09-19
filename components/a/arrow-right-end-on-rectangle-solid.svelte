<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s95tdh2ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s95tdh2ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-end-on-rectangle-solid" {...props}></Icon>
