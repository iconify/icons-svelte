<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7z7vbbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7z7vbbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netflix-alt2" {...props}></Icon>
