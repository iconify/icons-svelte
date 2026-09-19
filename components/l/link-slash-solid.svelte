<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rck100efq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rck100efq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:link-slash-solid" {...props}></Icon>
