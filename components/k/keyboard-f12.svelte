<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od5wrcgjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od5wrcgjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-f12" {...props}></Icon>
