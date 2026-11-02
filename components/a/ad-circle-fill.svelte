<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdi86dvjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdi86dvjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-circle-fill" {...props}></Icon>
