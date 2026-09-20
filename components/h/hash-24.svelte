<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wemig523u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wemig523u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:hash-24" {...props}></Icon>
