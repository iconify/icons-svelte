<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oocjo8pxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oocjo8pxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:radio1" {...props}></Icon>
