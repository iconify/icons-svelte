<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lklfmxbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lklfmxbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-minimalistic-bold" {...props}></Icon>
