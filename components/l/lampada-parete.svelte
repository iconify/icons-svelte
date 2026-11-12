<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq-83c7lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq-83c7lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lampada-parete" {...props}></Icon>
