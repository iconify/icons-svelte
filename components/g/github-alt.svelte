<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfs7arb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfs7arb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:github-alt" {...props}></Icon>
