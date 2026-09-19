<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gs25nqb9b.css';
import '../../css/k/km66jmbju.css';
import '../../css/y/y35g5r12s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gs25nqb9b"/><path class="km66jmbju"/><path class="y35g5r12s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-yes-duotone" {...props}></Icon>
