<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj36_mt2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj36_mt2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fold" {...props}></Icon>
