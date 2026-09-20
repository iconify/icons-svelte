<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pudpqi95x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pudpqi95x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:jam" {...props}></Icon>
