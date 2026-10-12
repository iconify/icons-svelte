<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_r9uibzg.css';
import '../../css/g/gbd4jm86s.css';
import '../../css/z/zc_h-6bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_r9uibzg"/><path class="gbd4jm86s"/><path class="zc_h-6bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-check-filled" {...props}></Icon>
