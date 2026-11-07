<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu0j3abrz.css';
import '../../css/p/p-sbw3baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu0j3abrz"/><path clip-rule="evenodd" class="p-sbw3baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:meditation-round-bold" {...props}></Icon>
