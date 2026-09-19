<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqa3tkb1n.css';
import '../../css/c/cb3cg7-ot.css';
import '../../css/u/uwzplsnnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="cb3cg7-ot"/><path class="uwzplsnnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:long-arrow-right-up-solid" {...props}></Icon>
