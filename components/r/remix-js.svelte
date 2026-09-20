<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga6k13bfd.css';
import '../../css/e/e7xhl5x5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ga6k13bfd"/><path class="e7xhl5x5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:remix-js" {...props}></Icon>
