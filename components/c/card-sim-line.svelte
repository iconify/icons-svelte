<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn47rw0ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn47rw0ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:card-sim-line" {...props}></Icon>
