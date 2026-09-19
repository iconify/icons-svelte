<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cvs2z244w.css';
import '../../css/p/p8hky2b0f.css';
import '../../css/j/jkrbe9b9z.css';
import '../../css/g/g3fwlbwlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cvs2z244w"/><path class="p8hky2b0f"/><path class="jkrbe9b9z"/><circle class="g3fwlbwlw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-crop" {...props}></Icon>
