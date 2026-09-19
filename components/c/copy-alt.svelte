<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn777jbnb.css';
import '../../css/f/ff5-g6s7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn777jbnb"/><path class="ff5-g6s7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:copy-alt" {...props}></Icon>
