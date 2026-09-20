<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgnvp1com.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgnvp1com"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paper-plane" {...props}></Icon>
