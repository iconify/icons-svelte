<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxv70lfbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxv70lfbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-plus" {...props}></Icon>
