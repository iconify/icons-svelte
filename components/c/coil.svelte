<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm2pvabdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm2pvabdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:coil" {...props}></Icon>
