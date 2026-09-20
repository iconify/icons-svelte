<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg2nftvpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zg2nftvpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ambulance-solid" {...props}></Icon>
