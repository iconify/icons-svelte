<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dipnjccbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dipnjccbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:horse-round" {...props}></Icon>
