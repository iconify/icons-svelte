<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/a/ah3rb_p1t.css';
import '../../css/c/cxbcwlbjn.css';
import '../../css/e/esdp5pbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsFy0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsFy0)"><path class="ah3rb_p1t"/><path class="cxbcwlbjn"/><path class="esdp5pbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:fy" {...props}></Icon>
