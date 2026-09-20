<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpbqijbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbqijbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:input-checked" {...props}></Icon>
