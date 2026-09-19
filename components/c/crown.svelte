<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua_pdg2wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua_pdg2wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:crown" {...props}></Icon>
