<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c-m63qg-e.css';
import '../../css/p/pe7zzcn4c.css';
import '../../css/e/e6b6ro_mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="c-m63qg-e"/><path class="pe7zzcn4c"/><path class="e6b6ro_mc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:git-cherry-pick" {...props}></Icon>
