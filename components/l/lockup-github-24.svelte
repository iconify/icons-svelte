<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn4spobzw.css';
import '../../css/g/gu1h78e1r.css';
import '../../css/b/bx3clim8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":103,"height":24};
const content = `<path class="kn4spobzw"/><path class="gu1h78e1r"/><path class="bx3clim8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:lockup-github-24" {...props}></Icon>
