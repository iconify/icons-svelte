<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thd_9hsjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thd_9hsjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:leaf" {...props}></Icon>
