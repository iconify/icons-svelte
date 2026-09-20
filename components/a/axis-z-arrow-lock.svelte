<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc9ac_byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc9ac_byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-z-arrow-lock" {...props}></Icon>
