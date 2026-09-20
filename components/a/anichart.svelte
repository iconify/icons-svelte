<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmns8ghnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmns8ghnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anichart" {...props}></Icon>
