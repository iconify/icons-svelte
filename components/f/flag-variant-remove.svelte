<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpoc7h0yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpoc7h0yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-remove" {...props}></Icon>
