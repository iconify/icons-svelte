<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw5jzub_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw5jzub_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:pod" {...props}></Icon>
