<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibcf01c0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibcf01c0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-template-24" {...props}></Icon>
