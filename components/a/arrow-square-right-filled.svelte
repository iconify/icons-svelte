<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk2jde1-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2jde1-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-square-right-filled" {...props}></Icon>
