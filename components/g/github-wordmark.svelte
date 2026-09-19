<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdptjablm.css';
import '../../css/r/rh99p0mbj.css';
import '../../css/b/b27n8hp7k.css';
import '../../css/y/yg15a6-lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="tdptjablm"><path clip-rule="evenodd" class="rh99p0mbj"/><path class="b27n8hp7k"/></g><path class="yg15a6-lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:github-wordmark" {...props}></Icon>
