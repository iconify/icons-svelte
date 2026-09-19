<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf2_v_89r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vf2_v_89r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bitcoinalt" {...props}></Icon>
