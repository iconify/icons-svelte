<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttgckubgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ttgckubgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-75" {...props}></Icon>
