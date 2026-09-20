<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoyx8fb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xoyx8fb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:play-circle" {...props}></Icon>
