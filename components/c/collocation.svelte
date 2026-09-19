<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwrkaoe0y.css';
import '../../css/o/oedplzbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwrkaoe0y"/><path class="oedplzbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:collocation" {...props}></Icon>
