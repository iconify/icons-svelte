<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly-_et2sc.css';
import '../../css/f/fkxo3pbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-_et2sc"/><path clip-rule="evenodd" class="fkxo3pbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-medicine-bold-duotone" {...props}></Icon>
