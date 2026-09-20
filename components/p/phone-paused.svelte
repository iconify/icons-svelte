<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miwm2wbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miwm2wbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-paused" {...props}></Icon>
