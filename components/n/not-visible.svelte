<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zac0kobyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zac0kobyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:not-visible" {...props}></Icon>
