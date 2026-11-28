<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsxk-l3nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxk-l3nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:moon-solid" {...props}></Icon>
