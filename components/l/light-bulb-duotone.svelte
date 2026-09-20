<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzi254bkh.css';
import '../../css/j/j-f4z-bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzi254bkh"/><path class="j-f4z-bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:light-bulb-duotone" {...props}></Icon>
