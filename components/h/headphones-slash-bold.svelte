<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdef5ccna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zdef5ccna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:headphones-slash-bold" {...props}></Icon>
