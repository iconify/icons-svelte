<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlc_h_b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlc_h_b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:box-open-x" {...props}></Icon>
