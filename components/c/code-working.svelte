<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgrlo48fn.css';
import '../../css/b/b-r1xf_2r.css';
import '../../css/x/x9trttupz.css';
import '../../css/s/si-h3sona.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fgrlo48fn"/><circle class="b-r1xf_2r"/><circle class="x9trttupz"/><path class="si-h3sona"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:code-working" {...props}></Icon>
