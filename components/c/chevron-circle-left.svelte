<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcf9opbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcf9opbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevron-circle-left" {...props}></Icon>
