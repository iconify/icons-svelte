<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sljfn47mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sljfn47mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-americas-solid" {...props}></Icon>
