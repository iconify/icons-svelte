<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk30w7bqn.css';
import '../../css/e/e_r9uibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yk30w7bqn"/><path class="e_r9uibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:printer-check-filled" {...props}></Icon>
