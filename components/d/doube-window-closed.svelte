<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trs6t6_2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trs6t6_2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:doube-window-closed" {...props}></Icon>
