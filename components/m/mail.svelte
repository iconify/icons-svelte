<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7j8yz-sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7j8yz-sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:mail" {...props}></Icon>
