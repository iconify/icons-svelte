<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib_exgb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib_exgb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ensis-up" {...props}></Icon>
