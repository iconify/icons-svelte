<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd-nkug3f.css';
import '../../css/s/s2cll7bjb.css';
import '../../css/g/ge8lssbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd-nkug3f"/><path class="s2cll7bjb"/><path class="ge8lssbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:registry-console-light" {...props}></Icon>
