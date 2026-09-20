<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn36lpbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn36lpbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:piaggiogroup" {...props}></Icon>
