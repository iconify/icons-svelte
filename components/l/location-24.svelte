<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlz_osbhr.css';
import '../../css/r/rwwu0mw7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlz_osbhr"/><path class="rwwu0mw7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:location-24" {...props}></Icon>
