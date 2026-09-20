<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-i_qcb0v.css';
import '../../css/h/ha04bdb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-i_qcb0v"/><path clip-rule="evenodd" class="ha04bdb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kasta" {...props}></Icon>
