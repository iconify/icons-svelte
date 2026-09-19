<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acem6c_hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acem6c_hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:jtexpress" {...props}></Icon>
