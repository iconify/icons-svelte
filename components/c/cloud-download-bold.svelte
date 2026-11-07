<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyax-g3ph.css';
import '../../css/j/jik0uqbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zyax-g3ph"/><path class="jik0uqbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-download-bold" {...props}></Icon>
