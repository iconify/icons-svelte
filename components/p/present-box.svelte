<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmqg9ef9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmqg9ef9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:present-box" {...props}></Icon>
