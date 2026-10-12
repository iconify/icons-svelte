<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t46oz2bvl.css';
import '../../css/j/j4v_2dxrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t46oz2bvl"/><path clip-rule="evenodd" class="j4v_2dxrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-stop-filled" {...props}></Icon>
