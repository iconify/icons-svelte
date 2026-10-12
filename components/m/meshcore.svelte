<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyz6b5bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyz6b5bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:meshcore" {...props}></Icon>
