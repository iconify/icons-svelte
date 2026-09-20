<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljapotbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljapotbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-hangup-outline" {...props}></Icon>
