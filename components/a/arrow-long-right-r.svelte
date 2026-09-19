<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjg90-bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wjg90-bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-right-r" {...props}></Icon>
