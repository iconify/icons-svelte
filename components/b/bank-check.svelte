<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aymr-nlwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aymr-nlwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-check" {...props}></Icon>
