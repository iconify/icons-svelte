<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akkkpkbzd.css';
import '../../css/j/jbxar0t6m.css';
import '../../css/f/flqk8ac0w.css';
import '../../css/h/h9ftfmbbj.css';
import '../../css/l/ljd0s_bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="akkkpkbzd"/><path class="jbxar0t6m"/><path class="flqk8ac0w"/><path class="h9ftfmbbj"/><circle class="ljd0s_bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikispecies" {...props}></Icon>
