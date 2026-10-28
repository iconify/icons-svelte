<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1zdf_6bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1zdf_6bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-bam" {...props}></Icon>
