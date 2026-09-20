<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn5_wcb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5_wcb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:btcturk" {...props}></Icon>
