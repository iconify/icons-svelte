<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtqicyzkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtqicyzkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:coffee" {...props}></Icon>
