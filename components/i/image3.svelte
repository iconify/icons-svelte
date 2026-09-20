<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-i-brbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-i-brbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:image3" {...props}></Icon>
