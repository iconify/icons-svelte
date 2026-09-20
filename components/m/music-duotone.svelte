<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rscdq9bxz.css';
import '../../css/y/y3964j9du.css';
import '../../css/u/ugx24zbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rscdq9bxz"/><path class="y3964j9du"/><path class="ugx24zbbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:music-duotone" {...props}></Icon>
