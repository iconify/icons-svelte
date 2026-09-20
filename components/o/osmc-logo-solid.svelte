<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/indlceb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="indlceb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:osmc-logo-solid" {...props}></Icon>
