<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncrdera-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncrdera-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pause" {...props}></Icon>
