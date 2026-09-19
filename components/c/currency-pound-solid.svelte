<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4ed2vbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4ed2vbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-pound-solid" {...props}></Icon>
