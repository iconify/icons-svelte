<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq2ums2ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq2ums2ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:point-down-solid" {...props}></Icon>
