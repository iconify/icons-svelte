<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eql-hlb0q.css';
import '../../css/b/bl436bbgz.css';
import '../../css/t/tikrs1biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eql-hlb0q"/><path class="bl436bbgz"/><path class="tikrs1biq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dumbbell-01" {...props}></Icon>
