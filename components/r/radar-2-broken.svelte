<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqe4w3b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqe4w3b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-broken" {...props}></Icon>
