<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym7f000we.css';
import '../../css/m/mz1_d65yo.css';
import '../../css/i/iq22m6bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym7f000we"/><path class="mz1_d65yo"/><path class="iq22m6bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:documents-bold" {...props}></Icon>
