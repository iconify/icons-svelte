<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvhor06rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvhor06rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dashboard-1-solid" {...props}></Icon>
