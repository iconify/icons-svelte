<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp1ly_bxy.css';
import '../../css/t/tuvamblkg.css';
import '../../css/i/i1958g00u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp1ly_bxy"/><rect class="tuvamblkg"/><path class="i1958g00u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:document-layout-right" {...props}></Icon>
