<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ipq_b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ipq_b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:jingle-bells-gloss" {...props}></Icon>
