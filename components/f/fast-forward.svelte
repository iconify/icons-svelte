<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrtgdmbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrtgdmbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:fast-forward" {...props}></Icon>
