<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_it4hbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_it4hbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:piv-unit" {...props}></Icon>
