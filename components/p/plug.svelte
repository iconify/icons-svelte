<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmroz-zfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmroz-zfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plug" {...props}></Icon>
