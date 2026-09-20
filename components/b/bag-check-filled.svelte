<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3snp07ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3snp07ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-check-filled" {...props}></Icon>
