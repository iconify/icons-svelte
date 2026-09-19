<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbc6z0ers.css';
import '../../css/s/s5gh9gbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zbc6z0ers"/><path class="s5gh9gbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ceph-wordmark" {...props}></Icon>
