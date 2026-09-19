<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at07s5byk.css';
import '../../css/n/n3ikn2b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="at07s5byk"/><circle class="n3ikn2b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:japanflag" {...props}></Icon>
