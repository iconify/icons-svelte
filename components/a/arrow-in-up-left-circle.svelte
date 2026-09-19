<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnep0m7rs.css';
import '../../css/z/zar1cn4so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnep0m7rs"/><path class="zar1cn4so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-left-circle" {...props}></Icon>
