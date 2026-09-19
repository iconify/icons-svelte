<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/z/zfr_yb1qg.css';
import '../../css/c/cyf5a0bja.css';
import '../../css/k/ko1gqibed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="zfr_yb1qg"/><path class="cyf5a0bja"/><path class="ko1gqibed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:mt" {...props}></Icon>
