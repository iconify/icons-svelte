<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj896_brl.css';
import '../../css/j/j22w93are.css';
import '../../css/q/qcswzebnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj896_brl"/><path class="j22w93are"/><path class="qcswzebnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-volume-filled" {...props}></Icon>
