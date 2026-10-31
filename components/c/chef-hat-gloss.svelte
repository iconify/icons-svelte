<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlgm7cbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlgm7cbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chef-hat-gloss" {...props}></Icon>
