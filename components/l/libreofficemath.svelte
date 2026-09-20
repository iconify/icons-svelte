<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1u7a9bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1u7a9bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:libreofficemath" {...props}></Icon>
