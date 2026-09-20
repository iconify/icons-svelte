<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j3r2uwbvw.css';
import '../../css/x/x6m8sibuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j3r2uwbvw"/><path clip-rule="evenodd" class="x6m8sibuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:filter-cancel-2" {...props}></Icon>
