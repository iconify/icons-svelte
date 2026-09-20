<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4023mu_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4023mu_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangular-prism-plus" {...props}></Icon>
