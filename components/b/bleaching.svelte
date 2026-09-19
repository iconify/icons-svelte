<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi-cwxbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi-cwxbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:bleaching" {...props}></Icon>
