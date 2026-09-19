<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk1co7rfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk1co7rfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-spot" {...props}></Icon>
