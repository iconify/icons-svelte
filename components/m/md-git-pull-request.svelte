<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkovc3a7g.css';
import '../../css/e/egti8_jds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkovc3a7g"/><path class="egti8_jds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-git-pull-request" {...props}></Icon>
