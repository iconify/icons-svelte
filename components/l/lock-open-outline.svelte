<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpwtk_bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpwtk_bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-open-outline" {...props}></Icon>
