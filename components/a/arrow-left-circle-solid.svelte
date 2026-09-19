<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr5d99b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wr5d99b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-circle-solid" {...props}></Icon>
