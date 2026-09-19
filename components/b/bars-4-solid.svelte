<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds9u897kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds9u897kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-4-solid" {...props}></Icon>
