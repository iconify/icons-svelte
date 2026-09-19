<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf20193bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf20193bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:align-text-left" {...props}></Icon>
