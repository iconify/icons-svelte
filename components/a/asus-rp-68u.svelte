<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtvz4qqfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtvz4qqfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:asus-rp-68u" {...props}></Icon>
