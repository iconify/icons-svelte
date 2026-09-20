<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3h95x70m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3h95x70m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pm2" {...props}></Icon>
