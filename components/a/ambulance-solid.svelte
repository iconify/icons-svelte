<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_e_q-1ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o_e_q-1ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ambulance-solid" {...props}></Icon>
