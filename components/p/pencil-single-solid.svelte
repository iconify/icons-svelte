<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt__1hb8y.css';
import '../../css/n/n7nwc9ecu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt__1hb8y"/><path clip-rule="evenodd" class="n7nwc9ecu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pencil-single-solid" {...props}></Icon>
