<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvnovvbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvnovvbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:odin" {...props}></Icon>
