<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scsc91bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scsc91bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:miele-scout" {...props}></Icon>
