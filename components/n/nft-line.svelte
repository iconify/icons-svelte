<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvt7osz7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvt7osz7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:nft-line" {...props}></Icon>
