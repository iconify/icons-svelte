<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n100ldbyg.css';
import '../../css/g/gzw5n1b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n100ldbyg"/><path class="gzw5n1b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:desktop-solid" {...props}></Icon>
