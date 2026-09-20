<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqc5__bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqc5__bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-open-settings" {...props}></Icon>
