<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxxxyimac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxxxyimac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:application-edit" {...props}></Icon>
