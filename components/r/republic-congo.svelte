<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7x-4e4hm.css';
import '../../css/x/x_t76jq2h.css';
import '../../css/f/fhw0kygnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="u7x-4e4hm"/><path class="x_t76jq2h"/><path class="fhw0kygnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:republic-congo" {...props}></Icon>
