<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrbh9lbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrbh9lbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ivi-tv" {...props}></Icon>
