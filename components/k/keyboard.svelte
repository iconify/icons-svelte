<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj0bo8wrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0bo8wrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:keyboard" {...props}></Icon>
