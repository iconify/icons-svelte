<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdzi00bpt.css';
import '../../css/l/lml2oc9mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="lml2oc9mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-chevron-up-square" {...props}></Icon>
