<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo4h86buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo4h86buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-remove-outline" {...props}></Icon>
