<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfba-8anb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfba-8anb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-look-left" {...props}></Icon>
