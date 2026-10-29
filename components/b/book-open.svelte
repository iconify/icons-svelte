<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzgfacbmm.css';
import '../../css/j/jci34lbfa.css';
import '../../css/v/vrhyijbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzgfacbmm"/><path class="jci34lbfa"/><path class="vrhyijbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:book-open" {...props}></Icon>
