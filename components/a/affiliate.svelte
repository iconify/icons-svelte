<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/shf4anbna.css';
import '../../css/x/x3xw6n-2f.css';
import '../../css/o/o8rexpb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="shf4anbna"/><path class="x3xw6n-2f"/><path class="o8rexpb5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:affiliate" {...props}></Icon>
