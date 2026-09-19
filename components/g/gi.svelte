<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/fkdjlyb2h.css';
import '../../css/l/loxo0lg5u.css';
import '../../css/b/b2iqgbb7z.css';
import '../../css/w/wwdrpthay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="fkdjlyb2h"/><path class="loxo0lg5u"/><path class="b2iqgbb7z"/><path class="wwdrpthay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:gi" {...props}></Icon>
