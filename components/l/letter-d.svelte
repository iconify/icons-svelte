<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk3s6ubsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk3s6ubsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-d" {...props}></Icon>
