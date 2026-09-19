<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sigcf32vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sigcf32vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:night-clear" {...props}></Icon>
