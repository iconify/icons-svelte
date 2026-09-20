<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl8aw5blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl8aw5blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:atlascloud" {...props}></Icon>
