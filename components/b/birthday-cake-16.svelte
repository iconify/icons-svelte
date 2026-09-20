<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhic9evto.css';
import '../../css/o/omhpelwiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uhic9evto"/><path class="omhpelwiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:birthday-cake-16" {...props}></Icon>
