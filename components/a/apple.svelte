<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlrchrjee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlrchrjee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:apple" {...props}></Icon>
