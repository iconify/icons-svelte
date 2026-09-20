<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-f8m-b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-f8m-b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aria20" {...props}></Icon>
