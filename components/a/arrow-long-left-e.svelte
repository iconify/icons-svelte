<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh4xrsbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bh4xrsbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-left-e" {...props}></Icon>
