<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh3igdb-g.css';
import '../../css/x/xtkb3wptd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lh3igdb-g"/><path class="xtkb3wptd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:argocd-wordmark" {...props}></Icon>
