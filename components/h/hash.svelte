<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6wia9bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6wia9bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:hash" {...props}></Icon>
