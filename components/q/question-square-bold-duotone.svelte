<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/z/z-85vlbmo.css';
import '../../css/x/x41xvfi0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="z-85vlbmo"/><path class="x41xvfi0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-square-bold-duotone" {...props}></Icon>
