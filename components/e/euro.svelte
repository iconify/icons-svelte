<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltpgq5bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltpgq5bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:euro" {...props}></Icon>
