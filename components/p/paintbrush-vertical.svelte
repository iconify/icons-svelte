<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/iwbjmpb4h.css';
import '../../css/d/d6lqux7jy.css';
import '../../css/j/ju36qx2re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="iwbjmpb4h"/><path class="d6lqux7jy"/><path class="ju36qx2re"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:paintbrush-vertical" {...props}></Icon>
