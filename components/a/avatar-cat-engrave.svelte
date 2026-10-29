<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b-fgsm7al.css';
import '../../css/z/zuvbbnbjg.css';
import '../../css/j/jqjkvibvj.css';
import '../../css/b/bcdke8buh.css';
import '../../css/o/o6_2u9-ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b-fgsm7al wm-k"/><path class="wm-a zuvbbnbjg"/><path class="jqjkvibvj wm-shadow"/><path class="bcdke8buh wm-k"/><path class="o6_2u9-ef wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-cat-engrave" {...props}></Icon>
