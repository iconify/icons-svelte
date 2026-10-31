<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0hf9xeyx.css';
import '../../css/h/h0ewzcb5r.css';
import '../../css/a/artvyv0ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o0hf9xeyx wm-k"/><path class="h0ewzcb5r wm-shine"/><path class="artvyv0ed wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:avatar-tiger" {...props}></Icon>
