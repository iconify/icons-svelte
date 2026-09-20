<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pijaru41s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pijaru41s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-minus" {...props}></Icon>
