<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqa7o6dfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jqa7o6dfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:map-solid" {...props}></Icon>
