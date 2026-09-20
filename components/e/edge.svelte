<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyw1rrbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyw1rrbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:edge" {...props}></Icon>
