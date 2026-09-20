<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfdz_fw0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfdz_fw0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:devexpress" {...props}></Icon>
