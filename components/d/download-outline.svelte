<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1fqb2bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1fqb2bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:download-outline" {...props}></Icon>
