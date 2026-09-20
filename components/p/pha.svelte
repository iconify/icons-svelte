<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzg73qn1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzg73qn1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pha" {...props}></Icon>
