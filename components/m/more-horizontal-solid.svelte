<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozuqne_mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozuqne_mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:more-horizontal-solid" {...props}></Icon>
