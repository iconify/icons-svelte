<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2z1e_f9o.css';
import '../../css/r/r79bbzbgk.css';
import '../../css/g/gsba024nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2z1e_f9o"/><path class="r79bbzbgk"/><path class="gsba024nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-close-bold-duotone" {...props}></Icon>
