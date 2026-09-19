<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm7t0fbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dm7t0fbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:plus-solid" {...props}></Icon>
