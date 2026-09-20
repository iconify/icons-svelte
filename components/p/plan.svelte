<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddlerbc9s.css';
import '../../css/w/w158vz8lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddlerbc9s"/><path class="w158vz8lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:plan" {...props}></Icon>
