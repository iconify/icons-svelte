<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk1uidbkm.css';
import '../../css/i/i191j5bfe.css';
import '../../css/s/sefr00bhg.css';
import '../../css/z/z9p97smkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qk1uidbkm"/><path class="i191j5bfe"/><path class="sefr00bhg"/><path class="z9p97smkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:dango" {...props}></Icon>
