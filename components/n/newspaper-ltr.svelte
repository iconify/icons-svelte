<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcxqr3faj.css';
import '../../css/u/ud305ub0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tcxqr3faj"/><path class="ud305ub0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:newspaper-ltr" {...props}></Icon>
