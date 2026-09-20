<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgyyitzgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgyyitzgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-forward-outline" {...props}></Icon>
