<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cexc4bw2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cexc4bw2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-remove-outline" {...props}></Icon>
