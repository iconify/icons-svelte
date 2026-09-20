<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltieuk1hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltieuk1hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:layer-group" {...props}></Icon>
