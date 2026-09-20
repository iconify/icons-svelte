<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re3r4xblg.css';
import '../../css/n/nq37i1bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re3r4xblg"/><path clip-rule="evenodd" class="nq37i1bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-locked-2-fill" {...props}></Icon>
