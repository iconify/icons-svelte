<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g46hbrb1d.css';
import '../../css/s/spboszblp.css';
import '../../css/z/zc_h-6bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g46hbrb1d"/><path class="spboszblp"/><path class="zc_h-6bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-x-filled" {...props}></Icon>
