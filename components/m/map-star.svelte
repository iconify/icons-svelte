<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsa0n1bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsa0n1bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-star" {...props}></Icon>
