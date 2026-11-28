<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9hc_l38j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9hc_l38j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plus-circle" {...props}></Icon>
