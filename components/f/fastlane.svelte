<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drtdhtb_j.css';
import '../../css/c/cqbmk1byz.css';
import '../../css/p/p5ypd6bpk.css';
import '../../css/q/qlqnfnb8d.css';
import '../../css/h/hxyfhfb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="drtdhtb_j"/><path class="cqbmk1byz"/><path class="p5ypd6bpk"/><path class="qlqnfnb8d"/><path class="hxyfhfb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:fastlane" {...props}></Icon>
